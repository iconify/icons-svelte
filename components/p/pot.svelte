<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqq6r_bhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqq6r_bhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:pot" {...props}></Icon>
