<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnsxrmu_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tnsxrmu_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:leaf-remix" {...props}></Icon>
