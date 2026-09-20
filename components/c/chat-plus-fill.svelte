<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bcb6e5lgd.css';
import '../../css/v/vk8rno99b.css';
import '../../css/o/oyqkr867s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bcb6e5lgd"/><path clip-rule="evenodd" class="vk8rno99b"/><path class="oyqkr867s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-plus-fill" {...props}></Icon>
