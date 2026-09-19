<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yanv2cchx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yanv2cchx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:chevron-double-up" {...props}></Icon>
