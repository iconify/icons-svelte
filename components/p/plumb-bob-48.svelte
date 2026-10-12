<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j5iw6acej.css';
import '../../css/e/esegazswt.css';
import '../../css/j/j46k23i9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j5iw6acej"/><path class="esegazswt"/><path class="j46k23i9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plumb-bob-48" {...props}></Icon>
