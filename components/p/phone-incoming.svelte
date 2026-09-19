<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maosicbit.css';
import '../../css/k/kggl2nbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="maosicbit"/><path class="kggl2nbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:phone-incoming" {...props}></Icon>
