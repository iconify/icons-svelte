<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz9b-3b4c.css';
import '../../css/f/fh-ustbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bz9b-3b4c"/><path class="fh-ustbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:calendar-check-2-filled" {...props}></Icon>
