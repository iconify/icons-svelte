<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5zwpxb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q5zwpxb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:factorial" {...props}></Icon>
