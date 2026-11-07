<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxghssbvs.css';
import '../../css/q/ql_va_b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxghssbvs"/><path clip-rule="evenodd" class="ql_va_b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-clock-bold" {...props}></Icon>
