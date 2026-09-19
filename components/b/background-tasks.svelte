<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgrkbtbto.css';
import '../../css/b/bdumtbccb.css';
import '../../css/d/de-emhyyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgrkbtbto"/><path class="bdumtbccb"/><path class="de-emhyyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:background-tasks" {...props}></Icon>
