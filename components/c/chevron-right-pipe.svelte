<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlim-7bcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlim-7bcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:chevron-right-pipe" {...props}></Icon>
