<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3j6brbtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b3j6brbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:corner-up-right-duotone" {...props}></Icon>
