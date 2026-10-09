<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjptc1oys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tjptc1oys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-spring-48" {...props}></Icon>
