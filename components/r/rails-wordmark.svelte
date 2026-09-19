<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ze3tw4bhu.css';
import '../../css/i/ikfvhgbtv.css';
import '../../css/t/tl-xxku-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ze3tw4bhu"/><path class="ikfvhgbtv"/><path class="tl-xxku-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:rails-wordmark" {...props}></Icon>
