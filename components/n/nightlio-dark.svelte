<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsj-lcc7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bsj-lcc7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nightlio-dark" {...props}></Icon>
