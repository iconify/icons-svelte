<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nors1t8an.css';
import '../../css/m/mr67hub_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nors1t8an"/><path class="mr67hub_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-20-bold" {...props}></Icon>
