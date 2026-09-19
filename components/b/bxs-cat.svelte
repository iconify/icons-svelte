<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4aexd1cu.css';
import '../../css/k/kpl5dzvml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4aexd1cu"/><path class="kpl5dzvml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-cat" {...props}></Icon>
