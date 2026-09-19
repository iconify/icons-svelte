<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf6tr1s3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mf6tr1s3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:blender-phone-solid" {...props}></Icon>
