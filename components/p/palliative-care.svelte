<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4r6l7h7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y4r6l7h7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:palliative-care" {...props}></Icon>
