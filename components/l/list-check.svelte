<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nv5s23ivq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nv5s23ivq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:list-check" {...props}></Icon>
