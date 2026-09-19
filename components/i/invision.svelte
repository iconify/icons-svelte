<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5747cl7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="o5747cl7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:invision" {...props}></Icon>
