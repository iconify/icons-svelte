<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hpz_xxn6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="hpz_xxn6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:gist-secret" {...props}></Icon>
