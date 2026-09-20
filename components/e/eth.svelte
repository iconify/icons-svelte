<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dor-qnbot.css';
import '../../css/u/uzfziisgz.css';
import '../../css/j/jv7_enpyu.css';
import '../../css/i/inlew3bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dor-qnbot"/><path class="uzfziisgz"/><path clip-rule="evenodd" class="jv7_enpyu"/><path clip-rule="evenodd" class="inlew3bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:eth" {...props}></Icon>
