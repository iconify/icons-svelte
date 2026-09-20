<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ent8d6byk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ent8d6byk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:foxtel" {...props}></Icon>
