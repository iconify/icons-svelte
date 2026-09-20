<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhroet0on.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhroet0on"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:number-2" {...props}></Icon>
