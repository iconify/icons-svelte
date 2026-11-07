<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz90m1b7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz90m1b7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-broken" {...props}></Icon>
