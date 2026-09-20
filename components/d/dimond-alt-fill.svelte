<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0r4ybbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i0r4ybbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:dimond-alt-fill" {...props}></Icon>
