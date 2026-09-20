<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/psn7qac5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="psn7qac5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:mood-silence" {...props}></Icon>
