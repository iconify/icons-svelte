<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rpw4bybvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rpw4bybvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-tick-solid" {...props}></Icon>
