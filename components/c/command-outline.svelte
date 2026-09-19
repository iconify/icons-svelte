<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9xfavm2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9xfavm2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:command-outline" {...props}></Icon>
