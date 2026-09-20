<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/e/eo90_nbnk.css';
import '../../css/z/z7apcccjt.css';
import '../../css/g/g15y3hbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="eo90_nbnk"/><path class="z7apcccjt"/><path class="g15y3hbeq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:password-type" {...props}></Icon>
