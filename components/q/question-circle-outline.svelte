<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt_dvue1n.css';
import '../../css/t/ts_bt_bky.css';
import '../../css/d/du6sep0xm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt_dvue1n"/><path class="ts_bt_bky"/><path clip-rule="evenodd" class="du6sep0xm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:question-circle-outline" {...props}></Icon>
