<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knj32rtjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knj32rtjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:more-vertical" {...props}></Icon>
