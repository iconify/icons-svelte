<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-0fpq8wv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-0fpq8wv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-code-outline" {...props}></Icon>
