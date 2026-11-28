<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scy0dybkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scy0dybkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arcade-machine-solid" {...props}></Icon>
