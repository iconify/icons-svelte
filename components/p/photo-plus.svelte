<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fawgp6okp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fawgp6okp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:photo-plus" {...props}></Icon>
