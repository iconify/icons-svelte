<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stv027biq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stv027biq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pen-edit-circle" {...props}></Icon>
