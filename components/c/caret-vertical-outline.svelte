<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-b-cfejk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y-b-cfejk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:caret-vertical-outline" {...props}></Icon>
