<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md7z81-3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md7z81-3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:comment-alt" {...props}></Icon>
