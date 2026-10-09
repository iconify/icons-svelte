<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dix-bwb7j.css';
import '../../css/u/ugwcjbfyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dix-bwb7j"/><path class="ugwcjbfyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydro-plant-20" {...props}></Icon>
