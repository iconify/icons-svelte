<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2j0xjy7g.css';
import '../../css/b/bdp2a1_-z.css';
import '../../css/d/d7fm7dbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f2j0xjy7g"/><path class="bdp2a1_-z"/><path class="d7fm7dbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-mail-light" {...props}></Icon>
