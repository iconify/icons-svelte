<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jueal6bpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jueal6bpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-to-top-right-broken" {...props}></Icon>
