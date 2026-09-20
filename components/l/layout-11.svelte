<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2-lxn0av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2-lxn0av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:layout-11" {...props}></Icon>
