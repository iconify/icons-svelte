<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttzz6hdgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttzz6hdgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing" {...props}></Icon>
