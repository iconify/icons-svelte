<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh60tvb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh60tvb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:maximize-alt-02" {...props}></Icon>
