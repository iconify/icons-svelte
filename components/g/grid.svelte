<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hebeg2bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hebeg2bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:grid" {...props}></Icon>
