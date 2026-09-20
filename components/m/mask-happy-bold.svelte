<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/th2-4rb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="th2-4rb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mask-happy-bold" {...props}></Icon>
