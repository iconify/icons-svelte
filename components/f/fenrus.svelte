<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uslf4acad.css';
import '../../css/p/pju2zkapd.css';
import '../../css/t/tvhnkin6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uslf4acad"/><path class="pju2zkapd"/><path class="tvhnkin6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fenrus" {...props}></Icon>
