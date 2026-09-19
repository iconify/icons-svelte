<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9bimvbjr.css';
import '../../css/w/w-h-j4bey.css';
import '../../css/t/t3lpz8b2k.css';
import '../../css/a/ah7dfb-3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9bimvbjr"/><path class="w-h-j4bey"/><path class="t3lpz8b2k"/><path class="ah7dfb-3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:data-transfer" {...props}></Icon>
