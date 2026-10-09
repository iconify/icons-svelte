<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywc2g1byu.css';
import '../../css/i/i4242jg8r.css';
import '../../css/t/tnw7ywizw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ywc2g1byu"/><path class="i4242jg8r"/><path class="tnw7ywizw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-train-48" {...props}></Icon>
