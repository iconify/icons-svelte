<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd0ufyboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yd0ufyboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:grid-lines-offset" {...props}></Icon>
