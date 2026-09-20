<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nooz18b2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nooz18b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:arrow-right-solid" {...props}></Icon>
