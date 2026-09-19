<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-dtdwb5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="q-dtdwb5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-rain" {...props}></Icon>
