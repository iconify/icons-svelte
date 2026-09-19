<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq0_fcblc.css';
import '../../css/o/ox5bagm_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b qq0_fcblc"/><path class="b ox5bagm_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pill-bottle-alt" {...props}></Icon>
