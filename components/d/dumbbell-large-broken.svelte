<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm88tsbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xm88tsbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbell-large-broken" {...props}></Icon>
