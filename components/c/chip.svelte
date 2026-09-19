<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpxx2s2wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wpxx2s2wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chip" {...props}></Icon>
