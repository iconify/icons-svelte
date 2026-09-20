<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1i4fmlal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1i4fmlal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:redo" {...props}></Icon>
