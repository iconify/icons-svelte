<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijm3kab7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ijm3kab7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:payload-light" {...props}></Icon>
