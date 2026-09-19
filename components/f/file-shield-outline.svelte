<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l98ww57lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l98ww57lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:file-shield-outline" {...props}></Icon>
