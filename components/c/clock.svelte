<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/taopki_li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="taopki_li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:clock" {...props}></Icon>
