<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qge9a_few.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qge9a_few"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:creality" {...props}></Icon>
