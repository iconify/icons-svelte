<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0t9246lm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z0t9246lm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:film" {...props}></Icon>
