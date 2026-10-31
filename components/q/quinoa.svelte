<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exdrxybls.css';
import '../../css/u/uwtui1bbw.css';
import '../../css/y/ymhw3xb4s.css';
import '../../css/q/qp7g17b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="exdrxybls"/><path class="uwtui1bbw"/><path class="ymhw3xb4s"/><path class="qp7g17b6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:quinoa" {...props}></Icon>
