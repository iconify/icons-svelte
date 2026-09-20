<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxbw6cbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxbw6cbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-8-small" {...props}></Icon>
