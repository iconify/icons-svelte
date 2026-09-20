<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lk5nleb3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lk5nleb3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:grav" {...props}></Icon>
