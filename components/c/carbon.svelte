<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qapg4nbep.css';
import '../../css/t/ttfe232er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qapg4nbep"/><path class="ttfe232er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:carbon" {...props}></Icon>
