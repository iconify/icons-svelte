<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpp8smbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qpp8smbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bold-solid" {...props}></Icon>
