<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql_242uqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ql_242uqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:http-que" {...props}></Icon>
