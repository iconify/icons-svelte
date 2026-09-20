<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha06gbbrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ha06gbbrn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:filter-solid" {...props}></Icon>
