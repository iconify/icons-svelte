<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw7ckupjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rw7ckupjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-right-large-duotone" {...props}></Icon>
