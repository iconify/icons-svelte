<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7fev4-_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7fev4-_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-merge-2-line" {...props}></Icon>
