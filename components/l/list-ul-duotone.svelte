<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjx1jgzfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjx1jgzfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:list-ul-duotone" {...props}></Icon>
