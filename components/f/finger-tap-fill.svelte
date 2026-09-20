<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmu2mhb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gmu2mhb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:finger-tap-fill" {...props}></Icon>
