<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8kduccib.css';
import '../../css/j/jr633_uxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8kduccib"/><path class="jr633_uxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:movr" {...props}></Icon>
