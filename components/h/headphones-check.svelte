<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acj_6hb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acj_6hb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:headphones-check" {...props}></Icon>
