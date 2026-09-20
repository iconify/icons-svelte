<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw0sli3kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw0sli3kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-golang" {...props}></Icon>
