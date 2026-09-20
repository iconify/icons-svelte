<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9opp6bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9opp6bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:helicopter-filled" {...props}></Icon>
