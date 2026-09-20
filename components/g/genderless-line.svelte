<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9bpxpb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9bpxpb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:genderless-line" {...props}></Icon>
