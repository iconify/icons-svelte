<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuj95b6oo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuj95b6oo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:project" {...props}></Icon>
