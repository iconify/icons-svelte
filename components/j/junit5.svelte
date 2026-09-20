<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve7xr_b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ve7xr_b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:junit5" {...props}></Icon>
