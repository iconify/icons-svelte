<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4yy3nb0m.css';
import '../../css/h/hxpwx2jys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4yy3nb0m"/><path class="hxpwx2jys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:chart-pie" {...props}></Icon>
