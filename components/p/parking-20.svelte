<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1oumu-ip.css';
import '../../css/d/dx356g9xe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a1oumu-ip"/><path class="dx356g9xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:parking-20" {...props}></Icon>
