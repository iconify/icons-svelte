<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcwvnabxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zcwvnabxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:lightbulb-solid" {...props}></Icon>
