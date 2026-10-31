<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipyreya2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ipyreya2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-single-clockwise-solid" {...props}></Icon>
