<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czi_pacop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="czi_pacop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-n" {...props}></Icon>
