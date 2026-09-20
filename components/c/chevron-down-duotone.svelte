<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cs1umdg9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cs1umdg9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chevron-down-duotone" {...props}></Icon>
