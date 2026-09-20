<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e42-bacmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e42-bacmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dandelion-line" {...props}></Icon>
