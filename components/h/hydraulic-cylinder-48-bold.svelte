<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0vfx9bkz.css';
import '../../css/k/kijssacqj.css';
import '../../css/q/qbege6bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="b0vfx9bkz"/><path class="kijssacqj"/><path class="qbege6bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydraulic-cylinder-48-bold" {...props}></Icon>
