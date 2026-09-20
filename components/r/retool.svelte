<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eodtv5b6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eodtv5b6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:retool" {...props}></Icon>
