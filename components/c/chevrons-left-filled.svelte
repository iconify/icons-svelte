<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfr5h3cft.css';
import '../../css/b/b4j54ubbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfr5h3cft"/><path class="b4j54ubbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevrons-left-filled" {...props}></Icon>
