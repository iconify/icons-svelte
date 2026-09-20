<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvu2o1bci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qvu2o1bci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:iphone" {...props}></Icon>
