<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8ksaubrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8ksaubrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-62-small" {...props}></Icon>
