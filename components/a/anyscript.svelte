<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3dnpkz9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3dnpkz9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:anyscript" {...props}></Icon>
