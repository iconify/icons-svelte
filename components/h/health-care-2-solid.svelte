<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih27f4boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ih27f4boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:health-care-2-solid" {...props}></Icon>
