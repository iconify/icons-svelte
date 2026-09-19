<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iox9jwa4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iox9jwa4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:leg" {...props}></Icon>
