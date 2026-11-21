<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii30vacbk.css';
import '../../css/f/fdr6bubwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii30vacbk"/><path class="fdr6bubwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:external-link-filled" {...props}></Icon>
