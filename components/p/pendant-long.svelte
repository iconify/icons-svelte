<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqoeek4zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqoeek4zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pendant-long" {...props}></Icon>
