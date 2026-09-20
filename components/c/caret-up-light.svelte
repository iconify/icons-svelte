<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcpe-v65l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wcpe-v65l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:caret-up-light" {...props}></Icon>
