<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-jb5hbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-jb5hbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:mobile-me-logo" {...props}></Icon>
