<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9jkobctp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y9jkobctp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mg" {...props}></Icon>
