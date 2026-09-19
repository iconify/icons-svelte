<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eoo1flbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eoo1flbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:lock-picking" {...props}></Icon>
