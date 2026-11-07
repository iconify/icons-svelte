<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jksbokb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jksbokb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hourglass-broken" {...props}></Icon>
