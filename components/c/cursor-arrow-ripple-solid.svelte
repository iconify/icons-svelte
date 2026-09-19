<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceq1he5nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ceq1he5nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:cursor-arrow-ripple-solid" {...props}></Icon>
