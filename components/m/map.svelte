<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mnapf6o7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="mnapf6o7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:map" {...props}></Icon>
