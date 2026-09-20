<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2vh7sqhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e2vh7sqhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mubi-logo-solid" {...props}></Icon>
