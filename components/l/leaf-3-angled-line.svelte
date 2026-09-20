<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn2855mwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn2855mwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:leaf-3-angled-line" {...props}></Icon>
