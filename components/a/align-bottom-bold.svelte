<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esgn2qmgb.css';
import '../../css/g/g1-qbmafx.css';
import '../../css/u/ul-233bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esgn2qmgb"/><path class="g1-qbmafx"/><path class="ul-233bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:align-bottom-bold" {...props}></Icon>
