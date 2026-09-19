<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbnqfqg8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qbnqfqg8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-four" {...props}></Icon>
