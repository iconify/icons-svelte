<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd-eh_bju.css';
import '../../css/s/s5nbh8u_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd-eh_bju"/><path class="s5nbh8u_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:copy-fill" {...props}></Icon>
