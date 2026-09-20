<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klqnr0qpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="klqnr0qpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:chat-text-fill" {...props}></Icon>
