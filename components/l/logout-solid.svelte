<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqlf7ffub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mqlf7ffub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:logout-solid" {...props}></Icon>
