<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o50glqbqr.css';
import '../../css/z/zglupmbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o50glqbqr"/><path class="zglupmbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:assemblyai" {...props}></Icon>
