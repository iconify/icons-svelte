<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xijfztbzl.css';
import '../../css/f/fu-ei7b7x.css';
import '../../css/o/ohcq6p68c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xijfztbzl"/><path class="fu-ei7b7x"/><path class="ohcq6p68c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:person-walking-48-bold" {...props}></Icon>
