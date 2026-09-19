<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii7we8yak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ii7we8yak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:music-off-filled" {...props}></Icon>
