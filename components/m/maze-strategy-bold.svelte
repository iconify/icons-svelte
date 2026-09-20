<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0q3n9bjy.css';
import '../../css/o/oi2dixb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0q3n9bjy"/><path class="oi2dixb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:maze-strategy-bold" {...props}></Icon>
