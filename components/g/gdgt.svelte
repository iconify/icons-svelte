<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk3cyc-gp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":488};
const content = `<path class="yk3cyc-gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:gdgt" {...props}></Icon>
