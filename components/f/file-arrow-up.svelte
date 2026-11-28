<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf146z00y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uf146z00y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-arrow-up" {...props}></Icon>
