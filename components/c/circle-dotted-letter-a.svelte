<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2addc-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr2addc-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dotted-letter-a" {...props}></Icon>
