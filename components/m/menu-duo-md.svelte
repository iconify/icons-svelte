<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsgw3bbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsgw3bbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:menu-duo-md" {...props}></Icon>
