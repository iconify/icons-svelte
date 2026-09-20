<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty-agzhxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty-agzhxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:credit-card-detailed-alt-line" {...props}></Icon>
