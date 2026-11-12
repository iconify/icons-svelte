<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7f8ufmsj.css';
import '../../css/b/bmz8mu02n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o7f8ufmsj"/><path class="bmz8mu02n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:geeftlist-light" {...props}></Icon>
