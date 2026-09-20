<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3i_3jbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3i_3jbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:inbox-2-fill" {...props}></Icon>
