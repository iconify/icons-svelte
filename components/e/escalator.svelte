<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaghidblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eaghidblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:escalator" {...props}></Icon>
