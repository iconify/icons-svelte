<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/m/mq8ul-5qi.css';
import '../../css/t/t4-ohwb_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path clip-rule="evenodd" class="mq8ul-5qi"/><path class="t4-ohwb_j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:analogue-logo" {...props}></Icon>
