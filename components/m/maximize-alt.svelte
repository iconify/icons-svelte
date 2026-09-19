<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2czy9tvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2czy9tvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:maximize-alt" {...props}></Icon>
