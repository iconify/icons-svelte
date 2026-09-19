<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjpbc1c8o.css';
import '../../css/m/mthptgvbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjpbc1c8o"/><path clip-rule="evenodd" class="mthptgvbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:battery-full-outline" {...props}></Icon>
