<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy62p4obt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="sy62p4obt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:battery-charging-f" {...props}></Icon>
