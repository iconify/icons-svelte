<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hp87_jb1i.css';
import '../../css/p/p8ldtcc9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hp87_jb1i"/><path class="p8ldtcc9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:keyboard-o" {...props}></Icon>
