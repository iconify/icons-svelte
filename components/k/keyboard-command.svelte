<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-p9n0bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-p9n0bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:keyboard-command" {...props}></Icon>
