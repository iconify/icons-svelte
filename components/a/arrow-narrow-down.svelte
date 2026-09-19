<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrsv_rb4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jrsv_rb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:arrow-narrow-down" {...props}></Icon>
