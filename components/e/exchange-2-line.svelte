<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0qmd-zhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0qmd-zhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:exchange-2-line" {...props}></Icon>
