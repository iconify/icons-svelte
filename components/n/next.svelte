<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6ir_ybos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="o6ir_ybos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:next" {...props}></Icon>
