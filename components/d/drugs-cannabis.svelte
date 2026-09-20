<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul8j8_bdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ul8j8_bdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:drugs-cannabis" {...props}></Icon>
