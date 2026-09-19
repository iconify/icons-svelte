<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv1jh76rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv1jh76rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:dashboard" {...props}></Icon>
