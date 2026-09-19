<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aubfdaczp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aubfdaczp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:archive-outline" {...props}></Icon>
