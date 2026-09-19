<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgtegnbft.css';
import '../../css/g/ge30ml4_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lgtegnbft"/><path class="ge30ml4_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-circle-half-filled" {...props}></Icon>
