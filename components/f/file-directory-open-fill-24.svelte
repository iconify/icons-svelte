<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsg1p1yyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsg1p1yyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-directory-open-fill-24" {...props}></Icon>
