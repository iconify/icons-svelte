<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/othmqysxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="othmqysxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:dialpad-solid" {...props}></Icon>
