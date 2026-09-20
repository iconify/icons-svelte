<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_5icd8xg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l_5icd8xg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number" {...props}></Icon>
