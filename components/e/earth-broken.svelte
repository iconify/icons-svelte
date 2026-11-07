<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar8y-0h1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar8y-0h1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:earth-broken" {...props}></Icon>
