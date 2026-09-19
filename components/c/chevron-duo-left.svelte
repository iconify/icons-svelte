<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1-jd7bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q1-jd7bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:chevron-duo-left" {...props}></Icon>
