<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snv4fbb_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snv4fbb_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:cloud-fog" {...props}></Icon>
