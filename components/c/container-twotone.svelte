<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opjpgxw-l.css';
import '../../css/l/liah705zk.css';
import '../../css/q/q9__elwgx.css';
import '../../css/q/q31a-k5ne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="opjpgxw-l"/><path class="liah705zk"/><path class="q9__elwgx"/><path class="q31a-k5ne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:container-twotone" {...props}></Icon>
