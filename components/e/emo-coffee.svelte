<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni-w6_bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1673,"height":1000};
const content = `<path class="ni-w6_bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-coffee" {...props}></Icon>
