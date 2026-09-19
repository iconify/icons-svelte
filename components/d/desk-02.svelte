<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qmr_aobwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qmr_aobwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:desk-02" {...props}></Icon>
