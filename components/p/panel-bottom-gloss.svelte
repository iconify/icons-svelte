<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixtq4fzpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixtq4fzpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:panel-bottom-gloss" {...props}></Icon>
