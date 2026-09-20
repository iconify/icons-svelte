<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeunnbwrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aeunnbwrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:flag-bend-sinister" {...props}></Icon>
