<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bacuuobnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bacuuobnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:logo-slack-20" {...props}></Icon>
