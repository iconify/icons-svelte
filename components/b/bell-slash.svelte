<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n52uadcfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="n52uadcfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:bell-slash" {...props}></Icon>
