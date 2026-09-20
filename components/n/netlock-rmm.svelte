<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxti2cc2i.css';
import '../../css/j/j3c-dicsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qxti2cc2i"/><path class="j3c-dicsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netlock-rmm" {...props}></Icon>
