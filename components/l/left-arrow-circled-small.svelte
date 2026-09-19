<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtdfgyb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="mtdfgyb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-arrow-circled-small" {...props}></Icon>
