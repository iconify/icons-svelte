<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmje_kq9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmje_kq9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-down-24" {...props}></Icon>
