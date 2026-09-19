<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1f9k7btv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":288,"height":512};
const content = `<path class="e1f9k7btv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mercury" {...props}></Icon>
