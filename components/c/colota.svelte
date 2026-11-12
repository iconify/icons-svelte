<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7c-2eb5a.css';
import '../../css/e/etsyzzgsk.css';
import '../../css/n/ntvq7ibes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x7c-2eb5a"/><path class="etsyzzgsk"/><path class="ntvq7ibes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:colota" {...props}></Icon>
