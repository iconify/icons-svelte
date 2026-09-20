<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g57bq_byt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g57bq_byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:circle-flask-remix" {...props}></Icon>
