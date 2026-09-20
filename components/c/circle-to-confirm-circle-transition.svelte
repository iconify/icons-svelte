<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/q/q9aucu.css';
import '../../css/c/czrd3c.css';
import '../../css/s/so-from-14.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c q9aucu"/><path class="a0m25c czrd3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:circle-to-confirm-circle-transition" {...props}></Icon>
