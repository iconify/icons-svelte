<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udehd1bxt.css';
import '../../css/y/yancwabok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="udehd1bxt"/><path class="yancwabok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:display" {...props}></Icon>
