<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar07nbijb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar07nbijb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:adjust" {...props}></Icon>
