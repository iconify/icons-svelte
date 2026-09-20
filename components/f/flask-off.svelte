<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rsr6lsg6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rsr6lsg6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:flask-off" {...props}></Icon>
