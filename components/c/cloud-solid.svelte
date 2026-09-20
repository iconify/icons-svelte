<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyubx5bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyubx5bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:cloud-solid" {...props}></Icon>
