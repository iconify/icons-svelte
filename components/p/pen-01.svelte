<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsqlp7fem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsqlp7fem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:pen-01" {...props}></Icon>
