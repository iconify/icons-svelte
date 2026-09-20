<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isbsl39ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isbsl39ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:monitor-down-line" {...props}></Icon>
