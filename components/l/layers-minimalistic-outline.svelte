<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz0c-7acw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz0c-7acw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:layers-minimalistic-outline" {...props}></Icon>
