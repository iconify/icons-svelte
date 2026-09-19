<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxgudgblm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="uxgudgblm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:mic-circle-fill" {...props}></Icon>
