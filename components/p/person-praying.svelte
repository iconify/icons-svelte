<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty_o-lgmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="ty_o-lgmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:person-praying" {...props}></Icon>
