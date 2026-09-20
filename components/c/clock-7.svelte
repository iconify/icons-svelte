<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d46mgrb0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d46mgrb0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-7" {...props}></Icon>
