<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js93vwb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="js93vwb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:line-app-logo-block" {...props}></Icon>
