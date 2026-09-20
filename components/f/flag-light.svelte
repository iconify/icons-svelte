<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-x_9nb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f-x_9nb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:flag-light" {...props}></Icon>
