<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2wycjbyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="b2wycjbyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:double-caret-left-outline" {...props}></Icon>
