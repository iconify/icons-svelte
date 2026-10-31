<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxt3a99fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rxt3a99fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-check-fill-round" {...props}></Icon>
