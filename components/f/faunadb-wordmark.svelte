<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef6n7ybih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ef6n7ybih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:faunadb-wordmark" {...props}></Icon>
