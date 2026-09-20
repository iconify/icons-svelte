<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvsnxacyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvsnxacyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-in-down-dashed-panel-sharp-fill" {...props}></Icon>
