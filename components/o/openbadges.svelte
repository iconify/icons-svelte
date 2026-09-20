<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyhs6fcbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyhs6fcbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:openbadges" {...props}></Icon>
