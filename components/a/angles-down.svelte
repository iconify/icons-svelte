<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h50rrzvxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h50rrzvxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:angles-down" {...props}></Icon>
