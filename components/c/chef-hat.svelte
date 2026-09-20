<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6xfscqbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6xfscqbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:chef-hat" {...props}></Icon>
