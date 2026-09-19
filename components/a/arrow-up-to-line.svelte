<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc6a3p-ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tc6a3p-ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-up-to-line" {...props}></Icon>
