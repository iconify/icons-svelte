<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htkm48jzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="htkm48jzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:devices-outline" {...props}></Icon>
