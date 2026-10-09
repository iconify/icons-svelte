<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibd5-t-ac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ibd5-t-ac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:anvil-48" {...props}></Icon>
