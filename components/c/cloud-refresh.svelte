<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgvyovbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgvyovbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cloud-refresh" {...props}></Icon>
