<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwr1d6buo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwr1d6buo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:new-section" {...props}></Icon>
