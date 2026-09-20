<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de42aeb0l.css';
import '../../css/y/yfn2vsbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="de42aeb0l"/><path clip-rule="evenodd" class="yfn2vsbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:gbc-solid" {...props}></Icon>
