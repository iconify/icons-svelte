<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqu6-wf_q.css';
import '../../css/f/f4sd7-1jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dqu6-wf_q"/><path class="f4sd7-1jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:external-link-20" {...props}></Icon>
