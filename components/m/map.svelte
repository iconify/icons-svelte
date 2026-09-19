<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8h_dobbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c8h_dobbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:map" {...props}></Icon>
