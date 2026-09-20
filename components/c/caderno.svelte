<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di5_344sf.css';
import '../../css/j/jpo8em2jn.css';
import '../../css/k/k5xw5glig.css';
import '../../css/g/g62l6wbpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="di5_344sf"/><path class="jpo8em2jn"/><path class="k5xw5glig"/><path class="g62l6wbpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:caderno" {...props}></Icon>
