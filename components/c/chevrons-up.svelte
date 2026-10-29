<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lndkskbcm.css';
import '../../css/u/ut80tnm-z.css';
import '../../css/p/pwyxzrs6i.css';
import '../../css/y/ys2kzn7au.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lndkskbcm wm-k"/><path class="ut80tnm-z wm-k"/><path class="pwyxzrs6i wm-a"/><path class="wm-a ys2kzn7au"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chevrons-up" {...props}></Icon>
