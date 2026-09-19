<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx9sqxq9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="wx9sqxq9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:arrow-uturn-right-circle-fill" {...props}></Icon>
