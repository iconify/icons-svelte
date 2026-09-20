<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j14jqwbgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j14jqwbgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:plurk-logo-1-solid" {...props}></Icon>
