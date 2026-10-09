<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcj6n3sgd.css';
import '../../css/f/f2--itp1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xcj6n3sgd"/><path class="f2--itp1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-pack-48-bold" {...props}></Icon>
