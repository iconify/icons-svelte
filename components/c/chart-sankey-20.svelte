<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itlombx0k.css';
import '../../css/c/cbxvuvbvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itlombx0k"/><path class="cbxvuvbvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-sankey-20" {...props}></Icon>
