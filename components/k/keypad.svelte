<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku3mnebwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ku3mnebwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:keypad" {...props}></Icon>
