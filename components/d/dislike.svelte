<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2qgdslvz.css';
import '../../css/o/o0xw4kbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r2qgdslvz"/><path class="o0xw4kbra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:dislike" {...props}></Icon>
