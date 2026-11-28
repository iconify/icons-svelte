<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knozg38db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knozg38db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:package-arrow-down" {...props}></Icon>
