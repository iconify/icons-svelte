<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_58wgb4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_58wgb4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ball-bowling" {...props}></Icon>
