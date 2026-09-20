<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c66xcebar.css';
import '../../css/a/at6xz-pmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c66xcebar"/><path class="at6xz-pmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:datasette" {...props}></Icon>
