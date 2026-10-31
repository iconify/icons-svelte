<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4b60ga7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b4b60ga7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-pause-gloss" {...props}></Icon>
