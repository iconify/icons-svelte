<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwj4e391z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="hwj4e391z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:free-code-camp" {...props}></Icon>
