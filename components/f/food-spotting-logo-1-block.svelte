<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejoikql5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ejoikql5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:food-spotting-logo-1-block" {...props}></Icon>
