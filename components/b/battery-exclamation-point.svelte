<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crr0vzbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crr0vzbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:battery-exclamation-point" {...props}></Icon>
