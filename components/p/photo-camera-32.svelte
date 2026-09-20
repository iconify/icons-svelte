<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/phr1lacdp.css';
import '../../css/c/cvbt36bli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="phr1lacdp"/><path clip-rule="evenodd" class="cvbt36bli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:photo-camera-32" {...props}></Icon>
