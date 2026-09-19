<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knvogvp8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knvogvp8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-top" {...props}></Icon>
