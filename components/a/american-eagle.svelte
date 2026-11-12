<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg0ripb9u.css';
import '../../css/p/p796kerln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="hg0ripb9u"/><path class="p796kerln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:american-eagle" {...props}></Icon>
