<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3-5_c46r.css';
import '../../css/c/clcnrxbew.css';
import '../../css/k/kihjjsb-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l3-5_c46r"/><path class="clcnrxbew"/><path class="kihjjsb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:koge" {...props}></Icon>
