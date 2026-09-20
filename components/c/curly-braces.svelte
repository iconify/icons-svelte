<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygghon35o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygghon35o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:curly-braces" {...props}></Icon>
