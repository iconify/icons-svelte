<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyb0-gxmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nyb0-gxmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pokemon" {...props}></Icon>
