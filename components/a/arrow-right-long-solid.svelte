<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bv8p7w18w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bv8p7w18w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-long-solid" {...props}></Icon>
