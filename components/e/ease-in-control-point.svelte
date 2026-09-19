<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2rplb5bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2rplb5bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:ease-in-control-point" {...props}></Icon>
