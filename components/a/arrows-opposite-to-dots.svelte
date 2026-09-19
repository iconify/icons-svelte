<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmmuu8bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rmmuu8bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrows-opposite-to-dots" {...props}></Icon>
