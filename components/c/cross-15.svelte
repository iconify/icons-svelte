<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8k7_7bkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b8k7_7bkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:cross-15" {...props}></Icon>
