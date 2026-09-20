<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w570xnbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w570xnbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-left-dashed-panel-fill" {...props}></Icon>
