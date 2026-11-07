<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5i5-fraq.css';
import '../../css/j/jurxy_blt.css';
import '../../css/n/na0l7yy-c.css';
import '../../css/u/udh7ivb4n.css';
import '../../css/z/zrjxdfbje.css';
import '../../css/r/rm2mun58o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5i5-fraq"/><path clip-rule="evenodd" class="jurxy_blt"/><path class="na0l7yy-c"/><path class="udh7ivb4n"/><path class="zrjxdfbje"/><path class="rm2mun58o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:balls-bold" {...props}></Icon>
