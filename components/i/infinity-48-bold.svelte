<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qww9sz6vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qww9sz6vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:infinity-48-bold" {...props}></Icon>
