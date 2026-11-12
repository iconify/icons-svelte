<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_ftkyb5l.css';
import '../../css/d/dm0klbgit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x_ftkyb5l"/><path class="dm0klbgit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickbars-dark" {...props}></Icon>
