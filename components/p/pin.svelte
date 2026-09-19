<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duvpq18rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":630,"height":850};
const content = `<path class="duvpq18rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:pin" {...props}></Icon>
