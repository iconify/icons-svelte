<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfxyw729p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfxyw729p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:four-finger-02" {...props}></Icon>
