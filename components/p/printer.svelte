<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2-tk3beh.css';
import '../../css/m/my7j9r31x.css';
import '../../css/j/jvw28gbdo.css';
import '../../css/v/vmlmfg8oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g2-tk3beh"/><path class="my7j9r31x"/><path class="jvw28gbdo"/><path class="vmlmfg8oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:printer" {...props}></Icon>
