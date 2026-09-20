<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keyan4-_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="keyan4-_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ballpen-filled" {...props}></Icon>
