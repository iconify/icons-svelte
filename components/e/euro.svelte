<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e27cdebky.css';
import '../../css/y/yjuc4p29b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e27cdebky"/><path class="yjuc4p29b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:euro" {...props}></Icon>
