<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsw5tr2lt.css';
import '../../css/i/ig6m21bsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hsw5tr2lt"/><path class="ig6m21bsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:crosshairs-24" {...props}></Icon>
