<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htkz26b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htkz26b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-right-sharp-fill" {...props}></Icon>
