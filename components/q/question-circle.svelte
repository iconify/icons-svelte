<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuedu7c-d.css';
import '../../css/j/j84tewqll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="kuedu7c-d"/><path class="j84tewqll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:question-circle" {...props}></Icon>
