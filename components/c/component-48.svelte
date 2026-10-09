<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opxm96fzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="opxm96fzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:component-48" {...props}></Icon>
