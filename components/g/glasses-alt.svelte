<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz2f2xxxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz2f2xxxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:glasses-alt" {...props}></Icon>
