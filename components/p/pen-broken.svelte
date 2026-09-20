<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j08t-ob-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j08t-ob-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pen-broken" {...props}></Icon>
