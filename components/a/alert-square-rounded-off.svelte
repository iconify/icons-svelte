<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj1be0vek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj1be0vek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:alert-square-rounded-off" {...props}></Icon>
