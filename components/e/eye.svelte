<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmg-50b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="jmg-50b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:eye" {...props}></Icon>
