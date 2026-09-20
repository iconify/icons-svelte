<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljt5gjl9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ljt5gjl9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gitea-dark" {...props}></Icon>
