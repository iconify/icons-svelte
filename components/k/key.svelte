<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn0_p-blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn0_p-blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key" {...props}></Icon>
