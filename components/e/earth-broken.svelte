<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ls4jinb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ls4jinb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:earth-broken" {...props}></Icon>
