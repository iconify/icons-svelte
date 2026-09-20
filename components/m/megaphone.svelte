<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haw94obwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="haw94obwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mi:megaphone" {...props}></Icon>
