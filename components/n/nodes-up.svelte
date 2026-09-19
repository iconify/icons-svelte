<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u01px0b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="u01px0b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:nodes-up" {...props}></Icon>
