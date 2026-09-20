<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h69cov3va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h69cov3va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-waterdrops-outline" {...props}></Icon>
