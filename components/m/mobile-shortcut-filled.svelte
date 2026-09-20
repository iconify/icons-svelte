<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdhskebrq.css';
import '../../css/l/l51b0lbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdhskebrq"/><path class="l51b0lbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mobile-shortcut-filled" {...props}></Icon>
