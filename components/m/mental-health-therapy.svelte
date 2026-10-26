<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwpoysb3f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="uwpoysb3f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:mental-health-therapy" {...props}></Icon>
