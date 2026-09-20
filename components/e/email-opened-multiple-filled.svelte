<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/al26zt.css';
import '../../css/a/a0m25c.css';
import '../../css/t/te6v-x.css';
import '../../css/z/z4421m.css';
import '../../css/q/qfvpsi.css';
import '../../css/f/fill-to-1.css';
import '../../css/s/so-from-64.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="al26zt"/><path class="a0m25c te6v-x"/><path class="a0m25c z4421m"/><path class="a0m25c qfvpsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:email-opened-multiple-filled" {...props}></Icon>
