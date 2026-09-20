<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca8yc2baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca8yc2baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bilibili-logo-block" {...props}></Icon>
