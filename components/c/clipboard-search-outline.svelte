<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c276uqo9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c276uqo9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-search-outline" {...props}></Icon>
