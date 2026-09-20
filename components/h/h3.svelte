<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhr_z3b9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhr_z3b9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:h3" {...props}></Icon>
