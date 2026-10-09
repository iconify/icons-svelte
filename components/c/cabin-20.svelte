<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7dkqbcdb.css';
import '../../css/e/enzpns2dp.css';
import '../../css/o/o3au9s7tu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7dkqbcdb"/><path class="enzpns2dp"/><path class="o3au9s7tu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cabin-20" {...props}></Icon>
