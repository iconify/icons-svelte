<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yje-c3cxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yje-c3cxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:panel-bottom-filled" {...props}></Icon>
