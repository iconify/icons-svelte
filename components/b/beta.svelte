<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro3ba9bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro3ba9bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beta" {...props}></Icon>
