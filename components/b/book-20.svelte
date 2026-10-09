<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udfsdub4u.css';
import '../../css/j/j18dvotij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="udfsdub4u"/><path class="j18dvotij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:book-20" {...props}></Icon>
