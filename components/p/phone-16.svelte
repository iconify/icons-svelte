<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwjk6jbnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qwjk6jbnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:phone-16" {...props}></Icon>
