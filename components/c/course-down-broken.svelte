<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpe-7kbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mpe-7kbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:course-down-broken" {...props}></Icon>
