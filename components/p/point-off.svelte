<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sahwddcek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sahwddcek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:point-off" {...props}></Icon>
