<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awwvp-plh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="awwvp-plh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:eye-optic-remix" {...props}></Icon>
