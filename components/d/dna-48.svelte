<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68xxsbdc.css';
import '../../css/q/qs2jqdb-s.css';
import '../../css/j/j46k23i9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b68xxsbdc"/><path class="qs2jqdb-s"/><path class="j46k23i9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dna-48" {...props}></Icon>
