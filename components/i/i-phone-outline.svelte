<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar8us1vws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ar8us1vws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:i-phone-outline" {...props}></Icon>
