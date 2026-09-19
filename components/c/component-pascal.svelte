<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia0lysvrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ia0lysvrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:component-pascal" {...props}></Icon>
