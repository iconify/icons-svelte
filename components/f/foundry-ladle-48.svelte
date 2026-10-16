<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yy0hggooi.css';
import '../../css/h/hi--g1d6e.css';
import '../../css/c/c65-ehvfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yy0hggooi"/><path class="hi--g1d6e"/><path class="c65-ehvfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:foundry-ladle-48" {...props}></Icon>
