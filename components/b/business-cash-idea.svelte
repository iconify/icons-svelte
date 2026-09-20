<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yrcchbbji.css';
import '../../css/j/jdbe-woge.css';
import '../../css/f/f-59ph3vy.css';
import '../../css/x/x4hixr_1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yrcchbbji"/><path class="jdbe-woge"/><path class="f-59ph3vy"/><path class="x4hixr_1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:business-cash-idea" {...props}></Icon>
