<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkb969b8t.css';
import '../../css/t/trm8ypqeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lkb969b8t"/><path class="trm8ypqeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:angle-double-right" {...props}></Icon>
