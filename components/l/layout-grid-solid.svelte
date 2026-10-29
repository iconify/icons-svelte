<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gugd7gbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gugd7gbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:layout-grid-solid" {...props}></Icon>
