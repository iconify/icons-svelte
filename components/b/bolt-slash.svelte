<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpk4ihbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tpk4ihbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bolt-slash" {...props}></Icon>
