<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaiyq5bvp.css';
import '../../css/p/pa98axbvh.css';
import '../../css/n/ngm4r3bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="qaiyq5bvp"><path class="pa98axbvh"/><path class="ngm4r3bsj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:adobe-ai" {...props}></Icon>
