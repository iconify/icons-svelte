<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pol6cgbck.css';
import '../../css/d/drobpt_me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pol6cgbck"/><path class="drobpt_me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:rocksdb" {...props}></Icon>
