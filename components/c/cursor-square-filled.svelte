<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcg8cukwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qcg8cukwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:cursor-square-filled" {...props}></Icon>
