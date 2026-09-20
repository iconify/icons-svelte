<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/h/hspje7bkl.css';
import '../../css/n/nsqwv68ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="hspje7bkl"/><path class="nsqwv68ki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:flu-mask-flat" {...props}></Icon>
