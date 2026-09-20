<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekj6e4b_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekj6e4b_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:kinsta" {...props}></Icon>
