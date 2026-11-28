<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2dszb9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2dszb9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:database-check" {...props}></Icon>
