<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nog_us2ey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nog_us2ey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:folder-plus" {...props}></Icon>
