<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujilh4b6o.css';
import '../../css/q/q9et3dbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ujilh4b6o"/><path class="q9et3dbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bandage-20-bold" {...props}></Icon>
