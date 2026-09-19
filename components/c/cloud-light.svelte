<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-2y0el6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-2y0el6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:cloud-light" {...props}></Icon>
