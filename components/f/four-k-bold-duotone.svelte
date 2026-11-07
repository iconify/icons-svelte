<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv_hji6de.css';
import '../../css/j/jvloipb8e.css';
import '../../css/e/e8g5qdb5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="jvloipb8e"/><path class="e8g5qdb5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:four-k-bold-duotone" {...props}></Icon>
