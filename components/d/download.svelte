<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ustd-of_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ustd-of_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:download" {...props}></Icon>
