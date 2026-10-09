<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njm7sdbty.css';
import '../../css/m/mazh1ozjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="njm7sdbty"/><path class="mazh1ozjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-open-48" {...props}></Icon>
