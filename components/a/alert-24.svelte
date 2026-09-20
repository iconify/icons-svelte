<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y69hv9biv.css';
import '../../css/r/ro3kpsbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y69hv9biv"/><path class="ro3kpsbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:alert-24" {...props}></Icon>
