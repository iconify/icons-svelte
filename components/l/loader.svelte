<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6xlo2b-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y6xlo2b-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:loader" {...props}></Icon>
