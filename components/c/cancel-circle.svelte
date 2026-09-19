<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fjpyzqc_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="fjpyzqc_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:cancel-circle" {...props}></Icon>
