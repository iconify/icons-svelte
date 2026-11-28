<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pct8yx7mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pct8yx7mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:file-refresh" {...props}></Icon>
