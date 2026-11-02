<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apx89dbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apx89dbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-horizontal-distribute-end-line" {...props}></Icon>
