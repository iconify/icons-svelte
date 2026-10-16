<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2mjsubix.css';
import '../../css/y/yut4brtiz.css';
import '../../css/i/iswbwirhc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h2mjsubix"/><path class="yut4brtiz"/><path class="iswbwirhc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-toxic-48-bold" {...props}></Icon>
