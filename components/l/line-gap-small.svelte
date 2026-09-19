<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mutex0f_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mutex0f_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:line-gap-small" {...props}></Icon>
