<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7gi09b7p.css';
import '../../css/i/i93jdftas.css';
import '../../css/c/c6-sq8xgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7gi09b7p"/><path class="i93jdftas"/><path class="c6-sq8xgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:release-24" {...props}></Icon>
