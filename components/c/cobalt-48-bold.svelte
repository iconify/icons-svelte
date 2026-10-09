<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omdaj5bmv.css';
import '../../css/c/cs3oflium.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="omdaj5bmv"/><path class="cs3oflium"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cobalt-48-bold" {...props}></Icon>
