<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ookrclnkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ookrclnkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cutlery-fill-12" {...props}></Icon>
