<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6jd2bx8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t6jd2bx8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:number-field" {...props}></Icon>
