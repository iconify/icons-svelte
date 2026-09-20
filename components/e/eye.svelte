<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlbd1zbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nlbd1zbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:eye" {...props}></Icon>
