<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-mnt58yd.css';
import '../../css/m/mu5v6jmij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b-mnt58yd"/><path class="mu5v6jmij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:information-square" {...props}></Icon>
