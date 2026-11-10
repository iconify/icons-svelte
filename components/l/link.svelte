<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt1rr2bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt1rr2bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:link" {...props}></Icon>
