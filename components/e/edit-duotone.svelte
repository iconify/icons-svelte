<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfp4bcqla.css';
import '../../css/v/viclgbp1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfp4bcqla"/><path class="viclgbp1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:edit-duotone" {...props}></Icon>
