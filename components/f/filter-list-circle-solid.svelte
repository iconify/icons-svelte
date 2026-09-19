<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/noday15di.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="noday15di"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:filter-list-circle-solid" {...props}></Icon>
