<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y893vacol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":472};
const content = `<path class="y893vacol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:maximum-temp-110-230" {...props}></Icon>
