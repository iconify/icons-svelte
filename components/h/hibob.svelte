<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbo6n2bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbo6n2bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hibob" {...props}></Icon>
