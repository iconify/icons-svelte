<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/ja0-wk5fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ja0-wk5fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:receipt-check" {...props}></Icon>
