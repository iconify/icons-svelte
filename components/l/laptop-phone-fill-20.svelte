<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svybeubux.css';
import '../../css/t/t6dqwebft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="svybeubux"/><path class="t6dqwebft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:laptop-phone-fill-20" {...props}></Icon>
