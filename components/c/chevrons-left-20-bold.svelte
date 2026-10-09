<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9umykbju.css';
import '../../css/e/esmbl8oyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s9umykbju"/><path class="esmbl8oyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-left-20-bold" {...props}></Icon>
