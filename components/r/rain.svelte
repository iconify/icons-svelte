<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nza059b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nza059b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:rain" {...props}></Icon>
