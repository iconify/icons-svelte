<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn2sbbcpi.css';
import '../../css/a/aevwtdbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kn2sbbcpi"/><path class="aevwtdbpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:laptop-phone-stroke-20" {...props}></Icon>
