<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jeeny6cmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jeeny6cmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:library-big" {...props}></Icon>
