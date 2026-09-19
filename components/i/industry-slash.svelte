<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dby-twbls.css';
import '../../css/b/bg9dcj-ic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dby-twbls"/><path class="bg9dcj-ic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:industry-slash" {...props}></Icon>
