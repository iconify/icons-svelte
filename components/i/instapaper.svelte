<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8npswbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="m8npswbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:instapaper" {...props}></Icon>
