<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvrc3e2gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvrc3e2gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:film-check" {...props}></Icon>
