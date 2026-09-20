<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5tjuwali.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x5tjuwali"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:plus-24" {...props}></Icon>
