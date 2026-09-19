<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl8kkut_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl8kkut_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:more-alt" {...props}></Icon>
