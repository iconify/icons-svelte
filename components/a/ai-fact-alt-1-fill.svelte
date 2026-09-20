<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm1bh9b5l.css';
import '../../css/n/n3p0cac3w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm1bh9b5l"/><path clip-rule="evenodd" class="n3p0cac3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:ai-fact-alt-1-fill" {...props}></Icon>
