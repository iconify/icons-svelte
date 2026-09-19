<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp7nw6bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cp7nw6bum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:phone-miss-outline" {...props}></Icon>
