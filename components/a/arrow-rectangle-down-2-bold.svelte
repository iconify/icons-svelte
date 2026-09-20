<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xeroz3p3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xeroz3p3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:arrow-rectangle-down-2-bold" {...props}></Icon>
