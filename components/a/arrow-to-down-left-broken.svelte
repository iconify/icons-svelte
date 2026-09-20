<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knoj3nbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knoj3nbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-down-left-broken" {...props}></Icon>
