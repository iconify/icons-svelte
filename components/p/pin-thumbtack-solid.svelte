<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe25r3bdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qe25r3bdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:pin-thumbtack-solid" {...props}></Icon>
