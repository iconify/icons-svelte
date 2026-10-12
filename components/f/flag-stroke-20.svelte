<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezcsx0bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ezcsx0bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:flag-stroke-20" {...props}></Icon>
