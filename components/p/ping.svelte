<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pd7ewqbeh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="pd7ewqbeh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:ping" {...props}></Icon>
