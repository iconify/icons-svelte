<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8f6-zbvd.css';
import '../../css/m/mg23doo2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m8f6-zbvd"/><path class="mg23doo2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-check-24" {...props}></Icon>
