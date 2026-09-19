<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tms9ahb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="tms9ahb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlezerply" {...props}></Icon>
