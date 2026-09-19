<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fren9q4hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fren9q4hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:info-circle-filled" {...props}></Icon>
