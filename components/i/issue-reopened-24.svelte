<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a804f_bji.css';
import '../../css/v/v5yyqhbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a804f_bji"/><path class="v5yyqhbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-reopened-24" {...props}></Icon>
