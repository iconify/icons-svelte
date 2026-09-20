<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lsm66sbym.css';
import '../../css/q/qtg25xsmx.css';
import '../../css/n/n7ttdxber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsm66sbym"/><path class="qtg25xsmx"/><path class="n7ttdxber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:reddit-alien-alt" {...props}></Icon>
