<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojhnb-a7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ojhnb-a7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:eslint" {...props}></Icon>
