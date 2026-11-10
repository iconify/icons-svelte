<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jatr1b-pp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jatr1b-pp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:list-ordered" {...props}></Icon>
