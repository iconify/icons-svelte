<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuujibcul.css';
import '../../css/k/kzsue3_rw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vuujibcul"/><path class="kzsue3_rw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:baidu" {...props}></Icon>
