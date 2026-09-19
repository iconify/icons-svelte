<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-6n8ccpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d-6n8ccpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-r" {...props}></Icon>
