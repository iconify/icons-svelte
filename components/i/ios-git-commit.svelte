<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koxdjkbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="koxdjkbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-git-commit" {...props}></Icon>
