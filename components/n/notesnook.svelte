<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7vo4nbxw.css';
import '../../css/x/x9vltugms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g7vo4nbxw"/><path class="x9vltugms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:notesnook" {...props}></Icon>
