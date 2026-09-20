<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amd21_i0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="amd21_i0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-stop-sharp" {...props}></Icon>
