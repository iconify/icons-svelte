<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzws7klud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yzws7klud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:data-transfer-horizontal" {...props}></Icon>
