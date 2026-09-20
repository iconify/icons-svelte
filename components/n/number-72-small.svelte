<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z64jbhwec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z64jbhwec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-72-small" {...props}></Icon>
