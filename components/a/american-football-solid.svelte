<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9t6t-b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9t6t-b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:american-football-solid" {...props}></Icon>
