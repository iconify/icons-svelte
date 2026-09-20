<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lo6nj3bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lo6nj3bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:flag-chequered" {...props}></Icon>
