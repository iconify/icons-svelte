<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0v_3bbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c0v_3bbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:contact-phonebook-2-remix" {...props}></Icon>
