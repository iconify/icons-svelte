<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2ju8nk3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ju8nk3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:laravel-logo-2" {...props}></Icon>
