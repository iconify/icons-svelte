<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoz70-7uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uoz70-7uy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:list-ul" {...props}></Icon>
