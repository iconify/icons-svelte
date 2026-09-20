<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkdtg4bmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkdtg4bmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:check-circle-fill-24" {...props}></Icon>
