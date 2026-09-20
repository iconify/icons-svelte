<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkv-rvbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="hkv-rvbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:circle-flask-flat" {...props}></Icon>
