<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwnw9_bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwnw9_bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:lifebuoy" {...props}></Icon>
