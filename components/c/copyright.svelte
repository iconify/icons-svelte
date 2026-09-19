<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynhhlqb6o.css';
import '../../css/h/hu5x0zz5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ynhhlqb6o"/><path class="hu5x0zz5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:copyright" {...props}></Icon>
