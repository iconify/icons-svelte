<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz3unxo7b.css';
import '../../css/c/cgvyvxz3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iz3unxo7b"/><path class="cgvyvxz3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-table-reference" {...props}></Icon>
