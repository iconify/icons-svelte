<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cicrr7b6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cicrr7b6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:check-square" {...props}></Icon>
