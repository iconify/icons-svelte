<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snp3cqm3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snp3cqm3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bike-solid" {...props}></Icon>
