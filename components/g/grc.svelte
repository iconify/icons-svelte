<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiy_jr2tf.css';
import '../../css/a/azjswrsrh.css';
import '../../css/n/n9w5lobwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jiy_jr2tf"/><path class="azjswrsrh"/><path class="n9w5lobwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:grc" {...props}></Icon>
