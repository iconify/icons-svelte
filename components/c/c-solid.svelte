<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk9ls1b5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="kk9ls1b5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:c-solid" {...props}></Icon>
