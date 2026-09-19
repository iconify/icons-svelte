<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr5-lrekc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tr5-lrekc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cpu-chip" {...props}></Icon>
