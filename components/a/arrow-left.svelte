<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo8dgkb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xo8dgkb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-left" {...props}></Icon>
