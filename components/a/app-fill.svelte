<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpcg-pb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="tpcg-pb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:app-fill" {...props}></Icon>
