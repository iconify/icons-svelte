<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk-2vtw8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk-2vtw8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:id-card-line" {...props}></Icon>
