<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk1m2mpra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk1m2mpra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:airpods-fill" {...props}></Icon>
