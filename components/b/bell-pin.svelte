<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lmlrhtz8r.css';
import '../../css/w/wptudbbot.css';
import '../../css/k/kl2jsebar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lmlrhtz8r"/><path class="wptudbbot"/><circle class="kl2jsebar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:bell-pin" {...props}></Icon>
