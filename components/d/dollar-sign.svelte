<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id-pioxhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id-pioxhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dollar-sign" {...props}></Icon>
