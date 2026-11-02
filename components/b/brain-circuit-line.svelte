<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol4q83bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol4q83bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brain-circuit-line" {...props}></Icon>
