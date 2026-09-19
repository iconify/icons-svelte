<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5kp83b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="k5kp83b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:person-booth" {...props}></Icon>
