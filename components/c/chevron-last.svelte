<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz9otiizw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz9otiizw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:chevron-last" {...props}></Icon>
