<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph-t_0mkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ph-t_0mkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:circle-letter-p" {...props}></Icon>
