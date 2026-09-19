<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8rpofbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8rpofbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:direction-up-right" {...props}></Icon>
