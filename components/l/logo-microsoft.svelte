<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hlswpooht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="hlswpooht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:logo-microsoft" {...props}></Icon>
