<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kiu_6cclx.css';
import '../../css/k/kc82gybja.css';
import '../../css/l/l2xkgdcaz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kiu_6cclx"/><rect class="kc82gybja"/><rect class="l2xkgdcaz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:between-vertical-start-filled" {...props}></Icon>
