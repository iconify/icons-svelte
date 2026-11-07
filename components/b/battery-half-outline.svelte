<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwmrmjbuw.css';
import '../../css/z/zgpdt1b9g.css';
import '../../css/y/ynwwsspwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwmrmjbuw"/><path class="zgpdt1b9g"/><path clip-rule="evenodd" class="ynwwsspwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-half-outline" {...props}></Icon>
