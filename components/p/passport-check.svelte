<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4hh4wuna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x4hh4wuna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:passport-check" {...props}></Icon>
