<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwiag_bln.css';
import '../../css/w/wzeup5m6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwiag_bln"/><path class="wzeup5m6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:rocket-alt" {...props}></Icon>
