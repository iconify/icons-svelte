<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp52dj2tx.css';
import '../../css/y/y5ok-dbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fp52dj2tx"/><path class="y5ok-dbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon" {...props}></Icon>
