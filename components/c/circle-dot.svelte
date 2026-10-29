<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyjo58brx.css';
import '../../css/o/or0-msbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yyjo58brx"/><path class="or0-msbfm wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:circle-dot" {...props}></Icon>
