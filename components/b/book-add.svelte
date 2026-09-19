<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa-ko1b3h.css';
import '../../css/c/ch6_fcbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa-ko1b3h"/><path class="ch6_fcbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:book-add" {...props}></Icon>
