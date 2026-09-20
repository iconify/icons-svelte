<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pk35wmbop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="pk35wmbop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:quote" {...props}></Icon>
