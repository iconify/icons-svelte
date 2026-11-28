<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_bn4ekm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ca_bn4ekm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:folder-input-solid" {...props}></Icon>
