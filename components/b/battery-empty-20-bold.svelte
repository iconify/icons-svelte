<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgrnoabib.css';
import '../../css/k/kjish1bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tgrnoabib"/><path class="kjish1bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-empty-20-bold" {...props}></Icon>
