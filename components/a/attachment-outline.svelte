<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jizitnexx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jizitnexx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:attachment-outline" {...props}></Icon>
