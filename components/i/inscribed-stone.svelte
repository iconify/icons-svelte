<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2rhd2bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="s2rhd2bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:inscribed-stone" {...props}></Icon>
