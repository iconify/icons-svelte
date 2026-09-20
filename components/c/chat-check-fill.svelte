<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o24enpbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o24enpbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:chat-check-fill" {...props}></Icon>
