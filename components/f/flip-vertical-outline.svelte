<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huh3he71t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="huh3he71t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:flip-vertical-outline" {...props}></Icon>
