<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmvyx4mlb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="lmvyx4mlb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circles-concentric" {...props}></Icon>
