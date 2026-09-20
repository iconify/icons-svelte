<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdc7ccqmw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wdc7ccqmw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:discord" {...props}></Icon>
