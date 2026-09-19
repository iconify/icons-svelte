<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fawxktbwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fawxktbwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chef-hat" {...props}></Icon>
