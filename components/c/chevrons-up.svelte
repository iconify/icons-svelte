<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4kb_cmha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4kb_cmha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:chevrons-up" {...props}></Icon>
