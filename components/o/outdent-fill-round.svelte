<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chu61h8mr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chu61h8mr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:outdent-fill-round" {...props}></Icon>
