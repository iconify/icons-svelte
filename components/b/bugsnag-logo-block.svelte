<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpjwubcxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lpjwubcxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bugsnag-logo-block" {...props}></Icon>
