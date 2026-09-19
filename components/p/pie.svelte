<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omrj64z5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":850};
const content = `<path class="omrj64z5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:pie" {...props}></Icon>
