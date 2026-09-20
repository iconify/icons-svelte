<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-ssnufuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-ssnufuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:forrst-logo" {...props}></Icon>
