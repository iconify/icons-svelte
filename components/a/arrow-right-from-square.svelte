<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0f7br4-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="f0f7br4-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:arrow-right-from-square" {...props}></Icon>
