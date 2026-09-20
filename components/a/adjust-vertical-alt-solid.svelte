<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htu_6ab6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="htu_6ab6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:adjust-vertical-alt-solid" {...props}></Icon>
