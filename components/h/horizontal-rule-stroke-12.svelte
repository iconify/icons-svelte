<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utd0fjb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="utd0fjb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:horizontal-rule-stroke-12" {...props}></Icon>
