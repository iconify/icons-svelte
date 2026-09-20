<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik-i4x10n.css';
import '../../css/c/chowghc9o.css';
import '../../css/s/s9kf_ac-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ik-i4x10n"/><path class="chowghc9o"/><path class="s9kf_ac-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:balance-duotone" {...props}></Icon>
