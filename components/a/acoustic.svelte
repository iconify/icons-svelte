<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufzd8ubbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ufzd8ubbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:acoustic" {...props}></Icon>
