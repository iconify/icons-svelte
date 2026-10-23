<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwf5wmqjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwf5wmqjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-6" {...props}></Icon>
