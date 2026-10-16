<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4geewbmp.css';
import '../../css/e/e57f5cgnd.css';
import '../../css/l/lo0zzvbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j4geewbmp"/><path class="e57f5cgnd"/><path class="lo0zzvbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ballot-box-48-bold" {...props}></Icon>
