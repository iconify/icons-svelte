<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lioq-n8vk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lioq-n8vk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:close-ring-fill" {...props}></Icon>
