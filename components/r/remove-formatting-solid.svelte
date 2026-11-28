<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/feolb4bfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="feolb4bfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:remove-formatting-solid" {...props}></Icon>
