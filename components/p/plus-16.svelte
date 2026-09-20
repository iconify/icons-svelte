<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ona9t_b2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ona9t_b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:plus-16" {...props}></Icon>
