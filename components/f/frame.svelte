<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m982-slos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m982-slos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:frame" {...props}></Icon>
