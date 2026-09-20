<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gedfccb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gedfccb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cellular-network-5g-remix" {...props}></Icon>
