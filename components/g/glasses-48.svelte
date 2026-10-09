<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4df3nkws.css';
import '../../css/j/jt1aqlbju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r4df3nkws"/><path class="jt1aqlbju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:glasses-48" {...props}></Icon>
