<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy4ci9b-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qy4ci9b-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:no-photo-taking-zone-solid" {...props}></Icon>
