<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cww23ibou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cww23ibou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:outdent-20-bold" {...props}></Icon>
