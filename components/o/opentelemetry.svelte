<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6ulv6bdt.css';
import '../../css/k/ku4u7fl3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z6ulv6bdt"/><path class="ku4u7fl3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:opentelemetry" {...props}></Icon>
