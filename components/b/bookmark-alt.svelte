<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctybheb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ctybheb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:bookmark-alt" {...props}></Icon>
