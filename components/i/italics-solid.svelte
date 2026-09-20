<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj049wbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj049wbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:italics-solid" {...props}></Icon>
