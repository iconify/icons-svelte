<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqax-6b-d.css';
import '../../css/r/rc6h4dq6f.css';
import '../../css/s/sjg59cb2m.css';
import '../../css/d/d-ekqwgrr.css';
import '../../css/q/qd4nuxbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="rc6h4dq6f"/><path class="sjg59cb2m"/><path class="d-ekqwgrr"/><path class="qd4nuxbqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:burger" {...props}></Icon>
