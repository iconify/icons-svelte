<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8_v07a_t.css';
import '../../css/l/lnl964nao.css';
import '../../css/z/z4zklhbom.css';
import '../../css/y/yzrr_8gta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8_v07a_t"/><path class="lnl964nao"/><path clip-rule="evenodd" class="z4zklhbom"/><path class="yzrr_8gta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-open-play-bold" {...props}></Icon>
