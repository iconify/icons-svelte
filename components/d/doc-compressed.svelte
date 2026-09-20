<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkszhcp6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lkszhcp6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:doc-compressed" {...props}></Icon>
