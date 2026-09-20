<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn45hr9iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn45hr9iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-lock-outline" {...props}></Icon>
