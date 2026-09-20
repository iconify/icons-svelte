<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm7m2abwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qm7m2abwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:file-cross-fill" {...props}></Icon>
