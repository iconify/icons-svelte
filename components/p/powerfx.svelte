<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am883v--m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="am883v--m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:powerfx" {...props}></Icon>
