<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y00dhxb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="y00dhxb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:clipboard" {...props}></Icon>
