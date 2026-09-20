<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acvs9ezds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acvs9ezds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:battery" {...props}></Icon>
