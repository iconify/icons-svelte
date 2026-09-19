<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfbn_4p6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mfbn_4p6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:flash-double" {...props}></Icon>
