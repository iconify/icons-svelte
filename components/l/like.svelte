<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2qgdslvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r2qgdslvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:like" {...props}></Icon>
