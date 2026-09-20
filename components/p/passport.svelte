<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkxqx5p1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkxqx5p1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:passport" {...props}></Icon>
