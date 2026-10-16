<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssxuq6bep.css';
import '../../css/i/i6mqdtdir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ssxuq6bep"/><path class="i6mqdtdir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heart-crack-20" {...props}></Icon>
