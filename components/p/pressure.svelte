<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud2bkbc2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ud2bkbc2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pressure" {...props}></Icon>
