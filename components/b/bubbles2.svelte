<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q29bvxb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="q29bvxb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bubbles2" {...props}></Icon>
