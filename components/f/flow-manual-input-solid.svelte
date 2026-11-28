<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_4v9bbaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_4v9bbaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-manual-input-solid" {...props}></Icon>
