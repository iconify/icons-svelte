<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh8422n_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh8422n_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ease-in-line" {...props}></Icon>
