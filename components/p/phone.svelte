<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgvi4xbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rgvi4xbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:phone" {...props}></Icon>
