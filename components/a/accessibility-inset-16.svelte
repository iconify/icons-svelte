<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev6n-jcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ev6n-jcqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:accessibility-inset-16" {...props}></Icon>
