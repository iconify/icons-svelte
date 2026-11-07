<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbtkp4_fw.css';
import '../../css/p/pfluh_2pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbtkp4_fw"/><path clip-rule="evenodd" class="pfluh_2pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:home-smile-outline" {...props}></Icon>
