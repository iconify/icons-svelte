<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz_ei8c0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vz_ei8c0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:circle-filled" {...props}></Icon>
