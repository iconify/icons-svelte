<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7cpylcvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7cpylcvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:chat-alt-add-fill" {...props}></Icon>
