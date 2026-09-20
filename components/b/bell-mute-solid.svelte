<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsrjsjbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsrjsjbxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:bell-mute-solid" {...props}></Icon>
