<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfdli4b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="bfdli4b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:american-football-11" {...props}></Icon>
