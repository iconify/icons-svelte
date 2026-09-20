<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-nk0j.css';
import '../../css/i/iw1iew.css';
import '../../css/a/ajozcb.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-46.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-nk0j iw1iew"/><path class="ajozcb iw1iew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:lightbulb-twotone" {...props}></Icon>
