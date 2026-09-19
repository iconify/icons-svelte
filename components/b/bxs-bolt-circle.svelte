<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njdwvrnbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njdwvrnbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bolt-circle" {...props}></Icon>
