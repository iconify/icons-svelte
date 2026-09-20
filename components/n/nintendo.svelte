<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkjt7ccve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xkjt7ccve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nintendo" {...props}></Icon>
