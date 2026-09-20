<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh90i4ezv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lh90i4ezv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:alarm-play" {...props}></Icon>
