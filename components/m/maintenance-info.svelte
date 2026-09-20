<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8b8fl31v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8b8fl31v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-info" {...props}></Icon>
