<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igqmfsbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2656,"height":2080};
const content = `<path class="igqmfsbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:male-female" {...props}></Icon>
