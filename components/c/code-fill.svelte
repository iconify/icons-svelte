<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1p7bbcjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c1p7bbcjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:code-fill" {...props}></Icon>
