<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvqw1eblr.css';
import '../../css/b/bugs1lbja.css';
import '../../css/w/wh6_lm8cy.css';
import '../../css/i/ik78sgb1x.css';
import '../../css/n/n4bf-vlvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvqw1eblr"/><path class="bugs1lbja"/><path class="wh6_lm8cy"/><path class="ik78sgb1x"/><path class="n4bf-vlvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-old-bold-duotone" {...props}></Icon>
