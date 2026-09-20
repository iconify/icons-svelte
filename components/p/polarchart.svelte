<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v49u3ub2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="v49u3ub2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:polarchart" {...props}></Icon>
