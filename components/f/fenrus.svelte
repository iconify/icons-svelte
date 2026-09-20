<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uslf4acad.css';
import '../../css/i/ia682rbyt.css';
import '../../css/r/r6heypbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uslf4acad"/><path class="ia682rbyt"/><path class="r6heypbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fenrus" {...props}></Icon>
