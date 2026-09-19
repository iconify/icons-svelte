<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kr82dzbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="kr82dzbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:film" {...props}></Icon>
