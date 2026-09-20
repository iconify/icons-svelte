<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohhvejblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohhvejblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kaufland" {...props}></Icon>
