<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao6e8934w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao6e8934w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:currency-tugrik" {...props}></Icon>
