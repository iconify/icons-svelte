<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl7kw49lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl7kw49lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:edit-filled" {...props}></Icon>
