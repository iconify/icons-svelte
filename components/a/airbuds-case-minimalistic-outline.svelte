<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5s-p9bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m5s-p9bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-case-minimalistic-outline" {...props}></Icon>
