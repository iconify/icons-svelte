<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx4asvbkn.css';
import '../../css/x/x9kjoyb1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx4asvbkn"/><path class="x9kjoyb1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:quora" {...props}></Icon>
