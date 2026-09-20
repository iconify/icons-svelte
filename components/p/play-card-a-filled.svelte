<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onktnwb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="onktnwb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:play-card-a-filled" {...props}></Icon>
