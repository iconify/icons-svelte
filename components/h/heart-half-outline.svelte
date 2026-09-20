<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkflt255p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkflt255p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:heart-half-outline" {...props}></Icon>
