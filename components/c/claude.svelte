<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt5nkhb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="kt5nkhb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:claude" {...props}></Icon>
