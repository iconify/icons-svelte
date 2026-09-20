<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur8ru8b9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ur8ru8b9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:apachenifi" {...props}></Icon>
