<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0ii7tboz.css';
import '../../css/j/jjdhgmbsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z0ii7tboz"/><path class="jjdhgmbsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nickel-20" {...props}></Icon>
