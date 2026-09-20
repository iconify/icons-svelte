<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zocpa-b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zocpa-b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-66-small" {...props}></Icon>
