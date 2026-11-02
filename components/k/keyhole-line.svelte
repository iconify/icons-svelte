<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk4d5qb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk4d5qb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:keyhole-line" {...props}></Icon>
