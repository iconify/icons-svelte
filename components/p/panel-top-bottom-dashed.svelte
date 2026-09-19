<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inkqubb7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inkqubb7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:panel-top-bottom-dashed" {...props}></Icon>
