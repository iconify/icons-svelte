<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwi__9bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwi__9bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:down-light" {...props}></Icon>
