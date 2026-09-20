<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jd2ny6bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jd2ny6bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:party-decoration-bold" {...props}></Icon>
