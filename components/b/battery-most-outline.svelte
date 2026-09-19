<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icho3y_ph.css';
import '../../css/m/mthptgvbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="icho3y_ph"/><path clip-rule="evenodd" class="mthptgvbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-most-outline" {...props}></Icon>
