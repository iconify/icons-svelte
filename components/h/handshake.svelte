<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oht4ataxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oht4ataxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:handshake" {...props}></Icon>
