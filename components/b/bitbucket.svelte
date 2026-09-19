<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqvr4v5ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqvr4v5ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:bitbucket" {...props}></Icon>
