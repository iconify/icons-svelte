<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f635f9k-l.css';
import '../../css/b/bx7cagbuz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="f635f9k-l"/><path class="bx7cagbuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-smoking" {...props}></Icon>
