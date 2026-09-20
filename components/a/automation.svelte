<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fih1jvc2u.css';
import '../../css/l/lgevicgqz.css';
import '../../css/y/ysv--kbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fih1jvc2u"/><path class="lgevicgqz"/><path class="ysv--kbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:automation" {...props}></Icon>
