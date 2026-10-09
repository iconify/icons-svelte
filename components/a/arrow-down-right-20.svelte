<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p52u5b7hp.css';
import '../../css/l/l9thhtagt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p52u5b7hp"/><path class="l9thhtagt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-down-right-20" {...props}></Icon>
