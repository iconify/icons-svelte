<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2h5hoimy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d2h5hoimy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-center-48-bold" {...props}></Icon>
