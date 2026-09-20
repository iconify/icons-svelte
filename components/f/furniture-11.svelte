<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z01ndpwmx.css';
import '../../css/q/qvqjn5baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="z01ndpwmx"/><path class="qvqjn5baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:furniture-11" {...props}></Icon>
