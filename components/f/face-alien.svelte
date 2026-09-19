<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mji93bd3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mji93bd3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:face-alien" {...props}></Icon>
