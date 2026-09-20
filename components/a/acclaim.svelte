<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj97_xb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj97_xb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:acclaim" {...props}></Icon>
