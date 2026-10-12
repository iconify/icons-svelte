<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxia6zz2s.css';
import '../../css/a/afzjcibgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rxia6zz2s"/><path class="afzjcibgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pi-20-bold" {...props}></Icon>
