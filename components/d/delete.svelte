<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm7dj77gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cm7dj77gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:delete" {...props}></Icon>
