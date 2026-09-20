<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pt4fctb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pt4fctb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-alt-3-fill" {...props}></Icon>
