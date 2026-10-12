<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz-ftvbge.css';
import '../../css/k/kespe5bzf.css';
import '../../css/a/aye8s_zkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cz-ftvbge"/><path class="kespe5bzf"/><path class="aye8s_zkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:layers-filled" {...props}></Icon>
