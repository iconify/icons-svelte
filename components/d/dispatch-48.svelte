<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir025xb6j.css';
import '../../css/k/kgirabbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ir025xb6j"/><path class="kgirabbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dispatch-48" {...props}></Icon>
