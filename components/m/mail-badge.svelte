<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hz7mn-15g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hz7mn-15g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mail-badge" {...props}></Icon>
