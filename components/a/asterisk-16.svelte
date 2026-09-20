<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxb14cb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qxb14cb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:asterisk-16" {...props}></Icon>
