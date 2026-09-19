<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3e159o-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x3e159o-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-graphics" {...props}></Icon>
