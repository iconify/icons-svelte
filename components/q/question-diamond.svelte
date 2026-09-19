<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb1q2tp7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="cb1q2tp7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:question-diamond" {...props}></Icon>
