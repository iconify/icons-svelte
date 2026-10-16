<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co0vf9bvy.css';
import '../../css/a/ao9i_zcjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="co0vf9bvy"/><path class="ao9i_zcjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:code-block-20" {...props}></Icon>
