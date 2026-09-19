<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sptkvotuc.css';
import '../../css/h/hs6ysgr6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="sptkvotuc"/><path class="hs6ysgr6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:results-demographics" {...props}></Icon>
