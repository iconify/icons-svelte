<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/staa6lb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="staa6lb3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:chart-bar-stacked-outline" {...props}></Icon>
