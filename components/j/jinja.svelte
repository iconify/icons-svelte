<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1685zbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g1685zbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jinja" {...props}></Icon>
