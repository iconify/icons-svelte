<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbch_7bfy.css';
import '../../css/y/y9fzgxb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hbch_7bfy"/><path class="y9fzgxb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:atm2" {...props}></Icon>
