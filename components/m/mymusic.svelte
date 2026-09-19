<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi8ojbzph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="vi8ojbzph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:mymusic" {...props}></Icon>
