<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp4rj4bzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jp4rj4bzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-j" {...props}></Icon>
