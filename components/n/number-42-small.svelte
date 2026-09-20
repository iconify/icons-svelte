<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq0aa8c7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq0aa8c7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-42-small" {...props}></Icon>
