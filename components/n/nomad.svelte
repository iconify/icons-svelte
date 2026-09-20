<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4yfrjbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4yfrjbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nomad" {...props}></Icon>
