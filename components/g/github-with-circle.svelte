<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cefb5cckj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cefb5cckj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:github-with-circle" {...props}></Icon>
