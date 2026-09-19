<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx3xw5bpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wx3xw5bpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:heart-pulse" {...props}></Icon>
