<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajh12op2y.css';
import '../../css/q/qtmpeuosr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajh12op2y"/><path class="qtmpeuosr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:git-pull-request-24" {...props}></Icon>
