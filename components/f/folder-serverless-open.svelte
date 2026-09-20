<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixetddbeg.css';
import '../../css/u/ud9xiabyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ixetddbeg"/><path class="ud9xiabyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-serverless-open" {...props}></Icon>
