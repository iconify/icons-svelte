<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzm83z9bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzm83z9bj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:copy" {...props}></Icon>
