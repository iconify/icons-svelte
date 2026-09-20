<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uhmaw1hfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uhmaw1hfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:origin" {...props}></Icon>
