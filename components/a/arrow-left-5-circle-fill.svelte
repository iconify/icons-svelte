<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_5bzbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k3_5bzbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-left-5-circle-fill" {...props}></Icon>
