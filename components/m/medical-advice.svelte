<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9wid4gvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="p9wid4gvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:medical-advice" {...props}></Icon>
