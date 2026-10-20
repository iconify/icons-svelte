<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cntw57bva.css';
import '../../css/q/q4ayogbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cntw57bva"/><path class="q4ayogbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:align-top-48-bold" {...props}></Icon>
