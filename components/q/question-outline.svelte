<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyn1h1bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cyn1h1bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:question-outline" {...props}></Icon>
