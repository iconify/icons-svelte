<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukz7ccbfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ukz7ccbfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:lightning-fill" {...props}></Icon>
