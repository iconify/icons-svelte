<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6ret3bta.css';
import '../../css/k/k1zg5jbzp.css';
import '../../css/s/sx_d_nlnk.css';
import '../../css/f/fc-nxccwx.css';
import '../../css/d/dq7yppiaz.css';
import '../../css/k/kr-tsdrut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6ret3bta"/><circle class="k1zg5jbzp"/><circle class="sx_d_nlnk"/><circle class="fc-nxccwx"/><circle class="dq7yppiaz"/><circle class="kr-tsdrut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:border-out" {...props}></Icon>
