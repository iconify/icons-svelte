<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxjp4lbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lxjp4lbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:museum-15" {...props}></Icon>
