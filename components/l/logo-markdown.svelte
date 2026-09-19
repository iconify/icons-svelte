<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nze9ryb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nze9ryb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:logo-markdown" {...props}></Icon>
