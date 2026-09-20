<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgh8dkykn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rgh8dkykn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-bolt" {...props}></Icon>
