<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yggatmbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yggatmbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:figma-logo-block" {...props}></Icon>
