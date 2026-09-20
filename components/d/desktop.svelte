<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnq2wwbiq.css';
import '../../css/e/exhairhvm.css';
import '../../css/i/iz_-1hojn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnq2wwbiq"/><path class="exhairhvm"/><path class="iz_-1hojn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:desktop" {...props}></Icon>
