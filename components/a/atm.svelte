<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bu00ooh-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bu00ooh-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:atm" {...props}></Icon>
