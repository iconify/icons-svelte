<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9uxiob0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f9uxiob0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:git-commit-sharp" {...props}></Icon>
