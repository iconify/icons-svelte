<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcnrjmbej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":654,"height":1000};
const content = `<path class="tcnrjmbej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:right-open" {...props}></Icon>
