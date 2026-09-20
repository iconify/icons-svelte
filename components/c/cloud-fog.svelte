<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awwk5gzrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awwk5gzrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-fog" {...props}></Icon>
