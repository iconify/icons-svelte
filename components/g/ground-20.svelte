<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rio2np7vm.css';
import '../../css/e/e2weyn4xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rio2np7vm"/><path class="e2weyn4xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ground-20" {...props}></Icon>
