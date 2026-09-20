<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcm-6bb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcm-6bb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-15-seconds-back-outline" {...props}></Icon>
