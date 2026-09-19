<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epoweac4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="epoweac4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:dice-1" {...props}></Icon>
