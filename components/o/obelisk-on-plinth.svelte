<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdo7bhahp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bdo7bhahp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:obelisk-on-plinth" {...props}></Icon>
