<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0qj-tuim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m0qj-tuim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-chevrons-up" {...props}></Icon>
