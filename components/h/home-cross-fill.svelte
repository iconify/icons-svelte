<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k6m704byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k6m704byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:home-cross-fill" {...props}></Icon>
