<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a588ydb6o.css';
import '../../css/a/axujlccoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a588ydb6o"/><path class="axujlccoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-baseball" {...props}></Icon>
