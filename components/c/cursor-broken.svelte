<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnn_g043v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnn_g043v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cursor-broken" {...props}></Icon>
