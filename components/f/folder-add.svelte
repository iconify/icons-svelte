<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sntofu_vz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sntofu_vz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:folder-add" {...props}></Icon>
