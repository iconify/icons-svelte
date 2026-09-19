<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1a2q6beh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":23,"height":24};
const content = `<path class="v1a2q6beh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:nav-icon-grid" {...props}></Icon>
