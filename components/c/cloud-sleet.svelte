<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovop27obc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ovop27obc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-sleet" {...props}></Icon>
