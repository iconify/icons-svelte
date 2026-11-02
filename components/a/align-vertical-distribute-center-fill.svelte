<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqxgb6byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqxgb6byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-distribute-center-fill" {...props}></Icon>
