<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me4702b8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me4702b8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:plus-circle" {...props}></Icon>
