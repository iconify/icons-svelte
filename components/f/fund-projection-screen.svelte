<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prq31rbnp.css';
import '../../css/u/u-0d80bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="prq31rbnp"/><path class="u-0d80bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:fund-projection-screen" {...props}></Icon>
