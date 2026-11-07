<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8rlbkdii.css';
import '../../css/s/stpgr5ezp.css';
import '../../css/h/h1b59mcwr.css';
import '../../css/s/sss82lbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8rlbkdii"/><path class="stpgr5ezp"/><path class="h1b59mcwr"/><path class="sss82lbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-4-bold" {...props}></Icon>
