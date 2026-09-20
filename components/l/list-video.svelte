<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu9u8zsfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9u8zsfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-video" {...props}></Icon>
