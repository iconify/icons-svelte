<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkenorbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kkenorbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:iceberg" {...props}></Icon>
