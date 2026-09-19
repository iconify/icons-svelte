<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/iofxxabca.css';
import '../../css/i/icjlvdb0c.css';
import '../../css/b/b7pyyhb0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iofxxabca"/><path class="icjlvdb0c"/><path class="b7pyyhb0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:quran-03" {...props}></Icon>
