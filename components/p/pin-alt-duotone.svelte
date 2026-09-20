<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/h_tg6mnbe.css';
import '../../css/z/zp7sorr7x.css';
import '../../css/c/chhunf30z.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGeN1KycjP"><g class="ft5dv1b6b"><path class="h_tg6mnbe"/><path class="zp7sorr7x"/><circle class="chhunf30z"/></g></mask></defs><path mask="url(#SVGeN1KycjP)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:pin-alt-duotone" {...props}></Icon>
