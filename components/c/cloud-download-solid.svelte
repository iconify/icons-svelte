<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6sn_6h4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6sn_6h4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cloud-download-solid" {...props}></Icon>
