<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1mh58hpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u1mh58hpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:balance-fill" {...props}></Icon>
