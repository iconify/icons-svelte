<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljh0thbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ljh0thbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dots-horizontal-fill" {...props}></Icon>
