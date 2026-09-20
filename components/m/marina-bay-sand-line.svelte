<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxae--4pg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxae--4pg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:marina-bay-sand-line" {...props}></Icon>
