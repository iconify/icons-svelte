<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qll2hmf4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qll2hmf4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bolt-filled" {...props}></Icon>
