<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5pjezhzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5pjezhzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:git-branch" {...props}></Icon>
