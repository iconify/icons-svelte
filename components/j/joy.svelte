<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhd2f7u1l.css';
import '../../css/d/dcvw64xgv.css';
import '../../css/s/scxamt7eq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhd2f7u1l"/><path class="dcvw64xgv"/><path class="scxamt7eq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:joy" {...props}></Icon>
