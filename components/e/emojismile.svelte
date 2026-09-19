<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6lc_ebxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="o6lc_ebxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:emojismile" {...props}></Icon>
