<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxg2qie0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="vxg2qie0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-heavyrain-fill" {...props}></Icon>
