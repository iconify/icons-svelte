<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxw-ku7it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="xxw-ku7it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:micro-sd-card-solid" {...props}></Icon>
