<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/fgf3lmnhv.css';
import '../../css/s/se9gb8bkp.css';
import '../../css/z/zagwpqb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fgf3lmnhv"/><path class="se9gb8bkp"/><path class="zagwpqb9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:quill-write-02" {...props}></Icon>
