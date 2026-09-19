<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzsl6bb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mzsl6bb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:card-spade" {...props}></Icon>
