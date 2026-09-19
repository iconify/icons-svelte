<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4iyz2z_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v4iyz2z_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:reply" {...props}></Icon>
